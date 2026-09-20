<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nr49v0bov.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nr49v0bov"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:government-line" /></template>
