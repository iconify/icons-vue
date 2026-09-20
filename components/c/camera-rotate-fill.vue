<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zq65rrbjc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zq65rrbjc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:camera-rotate-fill" /></template>
