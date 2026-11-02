<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rqzc2vbov.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rqzc2vbov"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:list-expansion-fill" /></template>
