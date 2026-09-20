<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wrppusbxi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="wrppusbxi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-flex:binoculars-solid" /></template>
