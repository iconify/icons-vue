<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mxpolhb6w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":12,"height":12};
const content = `<path class="mxpolhb6w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="dinkie-icons:extraterrestrial-alien" /></template>
