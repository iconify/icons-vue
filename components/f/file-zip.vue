<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xnk1gt9lb.css';
import '../../css/y/y4jnwib3d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="xnk1gt9lb"/><path class="y4jnwib3d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icomoon-free:file-zip" /></template>
