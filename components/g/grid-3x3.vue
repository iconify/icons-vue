<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hihb4h8dt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hihb4h8dt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vadivam:grid-3x3" /></template>
