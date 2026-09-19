<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fzkpz1bdj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":576,"height":512};
const content = `<path class="fzkpz1bdj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa-solid:hand-holding-medical" /></template>
