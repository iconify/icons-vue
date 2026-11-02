<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fas7ocjry.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fas7ocjry"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:check-line" /></template>
