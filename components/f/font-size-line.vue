<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sxpm3e1sb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="sxpm3e1sb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:font-size-line" /></template>
