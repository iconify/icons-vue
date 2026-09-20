<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j7fmnlb4r.css';
import '../../css/v/vaqln9rvn.css';
import '../../css/k/ko65f3b9d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="j7fmnlb4r"><path class="vaqln9rvn"/><path class="ko65f3b9d"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-ultimate:alert-octagon-1" /></template>
