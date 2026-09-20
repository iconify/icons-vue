<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m2a0xybtl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="m2a0xybtl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:girl" /></template>
