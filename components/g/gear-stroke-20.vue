<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jow4vojth.css';
import '../../css/k/k3_q2gqev.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="jow4vojth"/><path class="k3_q2gqev"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="garden:gear-stroke-20" /></template>
