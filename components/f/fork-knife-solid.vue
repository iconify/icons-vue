<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wqi_j-b4x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="wqi_j-b4x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-flex:fork-knife-solid" /></template>
