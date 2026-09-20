<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c83vp7b4u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="c83vp7b4u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-color:christian-cross-1-flat" /></template>
