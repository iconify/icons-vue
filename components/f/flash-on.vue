<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/ve-_k2a0b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="ve-_k2a0b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="flat-color-icons:flash-on" /></template>
