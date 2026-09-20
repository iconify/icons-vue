<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xssin9j6y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path class="xssin9j6y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-flex:align-selection" /></template>
