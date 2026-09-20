<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pfh0oxb8p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="pfh0oxb8p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:color-picker-solid" /></template>
