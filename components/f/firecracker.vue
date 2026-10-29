<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d2kvgvbvc.css';
import '../../css/g/gt83y5bri.css';
import '../../css/s/sq05rk26a.css';
import '../../css/o/o54drfbmd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="d2kvgvbvc"><path class="gt83y5bri"/><path class="sq05rk26a"/><path class="o54drfbmd"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons-bauhaus:firecracker" /></template>
