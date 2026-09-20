<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qav6brbvh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qav6brbvh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:format-vertical-align-centre" /></template>
