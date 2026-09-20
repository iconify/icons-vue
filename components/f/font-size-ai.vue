<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w4i-8mbgz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="w4i-8mbgz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:font-size-ai" /></template>
