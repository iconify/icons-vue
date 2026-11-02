<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y_oos2nfx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="y_oos2nfx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:circle-chevron-down-fill" /></template>
