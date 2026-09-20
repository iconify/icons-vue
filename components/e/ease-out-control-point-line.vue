<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vqtso2iev.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vqtso2iev"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:ease-out-control-point-line" /></template>
