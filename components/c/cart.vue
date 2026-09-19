<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yui_j73uu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="yui_j73uu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icomoon-free:cart" /></template>
