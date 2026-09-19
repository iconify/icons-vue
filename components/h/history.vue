<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pjp5kfbwt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":17,"height":16};
const content = `<path class="pjp5kfbwt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icomoon-free:history" /></template>
