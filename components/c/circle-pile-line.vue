<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/czm6z7bpm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="czm6z7bpm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:circle-pile-line" /></template>
