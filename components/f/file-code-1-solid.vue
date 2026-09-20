<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s-x1i7szn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="s-x1i7szn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-flex:file-code-1-solid" /></template>
