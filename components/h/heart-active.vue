<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n1p8bvb3l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="n1p8bvb3l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="nrk:heart-active" /></template>
