<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/ya2h1ewyu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path class="ya2h1ewyu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-color:flash-2-flat" /></template>
