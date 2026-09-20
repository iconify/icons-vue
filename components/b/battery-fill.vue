<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d-f2bfbaz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="d-f2bfbaz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:battery-fill" /></template>
