<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hqlfl2olr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hqlfl2olr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:font-size" /></template>
