<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/ytzi4p-xu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path class="ytzi4p-xu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-flex:cursor-click" /></template>
