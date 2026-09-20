<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gs3t96b4s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gs3t96b4s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mynaui:ar-solid" /></template>
