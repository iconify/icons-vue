<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fhzb-acko.css';
import '../../css/r/r1ceurbff.css';
import '../../css/z/zsl5jvb1i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fhzb-acko"/><path class="r1ceurbff"/><path class="zsl5jvb1i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bx:bxl-trip-advisor" /></template>
