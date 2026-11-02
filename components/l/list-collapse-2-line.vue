<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mneg3gbjr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mneg3gbjr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:list-collapse-2-line" /></template>
