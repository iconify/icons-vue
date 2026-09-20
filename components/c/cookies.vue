<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/n/n7mjf3bln.css';
import '../../css/s/sygtnjbkj.css';
import '../../css/z/z_1ytwpzb.css';
import '../../css/d/dzqtsubpx.css';
import '../../css/i/in4l2ib4e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="n7mjf3bln"/><circle class="sygtnjbkj"/><circle class="z_1ytwpzb"/><circle class="dzqtsubpx"/><circle class="in4l2ib4e"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="proicons:cookies" /></template>
