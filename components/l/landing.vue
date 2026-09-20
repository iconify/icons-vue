<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fjr1hxbnl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="fjr1hxbnl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-plump:landing" /></template>
