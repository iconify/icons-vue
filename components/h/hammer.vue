<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/toh6rgb4r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="toh6rgb4r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icomoon-free:hammer" /></template>
