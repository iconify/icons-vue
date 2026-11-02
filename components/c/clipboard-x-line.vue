<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u441x0bdc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="u441x0bdc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:clipboard-x-line" /></template>
