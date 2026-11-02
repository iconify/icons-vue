<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vxbi9rt5f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vxbi9rt5f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:alarm-1-line" /></template>
