<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hsto437ja.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="hsto437ja"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:arrow-reload-horizontal-1-solid" /></template>
