<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dt0cm9dhy.css';
import '../../css/z/zy9xw0nee.css';
import '../../css/g/g2ivodb2f.css';
import '../../css/v/vt-2nu9uw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="dt0cm9dhy"><path class="wm-a zy9xw0nee"/><path class="g2ivodb2f"/><path class="vt-2nu9uw wm-s"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:firecracker-string" /></template>
