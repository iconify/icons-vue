<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uaxe-znex.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="uaxe-znex"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:flash-1-solid" /></template>
