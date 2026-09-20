<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rq68h36xc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rq68h36xc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:corner-down-left-line" /></template>
