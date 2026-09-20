<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lnis27-yq.css';
import '../../css/s/s3n665z1h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lnis27-yq"/><path class="s3n665z1h"><animateTransform attributeName="transform" dur="0.75s" repeatCount="indefinite" type="rotate" values="0 12 12;360 12 12"/></path>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="svg-spinners:270-ring-with-bg" /></template>
