<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/alb4r-mom.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="alb4r-mom"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa-solid:hand-point-left" /></template>
