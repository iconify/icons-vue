<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f5jstv2qp.css';
import '../../css/u/uvian2ben.css';
import '../../css/p/p5n1y4wab.css';
import '../../css/h/hvka4mbsp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="f5jstv2qp"/><path class="uvian2ben"/><path class="p5n1y4wab"/><path class="hvka4mbsp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:connection-bars" /></template>
