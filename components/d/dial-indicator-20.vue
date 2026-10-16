<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y1wkb86ze.css';
import '../../css/u/u6d9mwu4u.css';
import '../../css/y/y18icnb3k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="y1wkb86ze"/><path class="u6d9mwu4u"/><path class="y18icnb3k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:dial-indicator-20" /></template>
