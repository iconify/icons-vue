<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/odtdr55ed.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="odtdr55ed"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:desktop-dollar-remix" /></template>
