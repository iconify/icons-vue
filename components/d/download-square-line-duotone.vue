<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ipq1z-bjh.css';
import '../../css/n/nrz63xv5c.css';
import '../../css/s/shxbccb1f.css';
import '../../css/w/wf89k6buf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="nrz63xv5c"/><path class="shxbccb1f"/><path class="wf89k6buf"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:download-square-line-duotone" /></template>
