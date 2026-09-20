<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/ru8kj1rep.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="ru8kj1rep"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:arrow-reload-vertical-1-solid" /></template>
