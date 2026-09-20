<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g2l5s7auk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="g2l5s7auk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-flex:flower-solid" /></template>
