<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/djmv0c3tz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="djmv0c3tz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-color:arrow-reload-vertical-1-flat" /></template>
