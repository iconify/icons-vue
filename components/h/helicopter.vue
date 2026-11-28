<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hf_d8cagc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hf_d8cagc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair:helicopter" /></template>
