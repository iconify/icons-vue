<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fwse9hejz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="fwse9hejz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-outline:figma-component" /></template>
