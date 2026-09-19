<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xhjb4mbgw.css';
import '../../css/v/vv_2udbvh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="xhjb4mbgw"/><path class="vv_2udbvh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="devicon:ansible" /></template>
