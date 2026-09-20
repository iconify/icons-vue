<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l-9crtsag.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="l-9crtsag"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:color-palette-solid" /></template>
