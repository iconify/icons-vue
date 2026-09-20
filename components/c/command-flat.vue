<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dddim5jqu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="dddim5jqu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-color:command-flat" /></template>
