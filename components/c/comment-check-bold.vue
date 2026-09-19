<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s0phu2bbs.css';
import '../../css/d/dzjoz5b9z.css';
import '../../css/k/k4wjgvq4n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="dzjoz5b9z"/><path class="k4wjgvq4n"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconamoon:comment-check-bold" /></template>
