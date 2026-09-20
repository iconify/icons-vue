<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hf1_53b8o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="hf1_53b8o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:coffee-mug-solid" /></template>
