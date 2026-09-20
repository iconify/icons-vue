<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u9nso0bqx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="u9nso0bqx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-color:color-palette-flat" /></template>
