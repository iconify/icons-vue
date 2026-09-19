<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d_ao4bbah.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="d_ao4bbah"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icomoon-free:attachment" /></template>
