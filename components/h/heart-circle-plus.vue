<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rkd7flewn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":576,"height":512};
const content = `<path class="rkd7flewn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-solid:heart-circle-plus" /></template>
