<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d0-arvhnl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="d0-arvhnl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:group-3-line" /></template>
