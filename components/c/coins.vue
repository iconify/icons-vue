<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/o/o8c9xvb5c.css';
import '../../css/j/j-we4za-r.css';
import '../../css/s/sno-j09lk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="o8c9xvb5c"/><path class="j-we4za-r"/><path class="sno-j09lk"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="majesticons:coins" /></template>
