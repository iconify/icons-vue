<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xn5eo9bqs.css';
import '../../css/g/g1_gbyj9e.css';
import '../../css/i/ihx5pgbrx.css';
import '../../css/a/ak1e8fwvs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="xn5eo9bqs"><path class="g1_gbyj9e"/><path class="ihx5pgbrx"/><path class="ak1e8fwvs"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="matita:graduation-cap" /></template>
