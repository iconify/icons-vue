<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/m/mgbhl21qs.css';
import '../../css/y/yo019rtxz.css';
import '../../css/i/il854jbvx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="mgbhl21qs"/><path class="yo019rtxz"/><path class="il854jbvx"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="heroicons-outline:academic-cap" /></template>
