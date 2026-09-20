<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e3il3ycro.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="e3il3ycro"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-flex:blank-calendar-solid" /></template>
