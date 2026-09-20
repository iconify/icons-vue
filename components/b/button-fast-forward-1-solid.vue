<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vuv56d10r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="vuv56d10r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:button-fast-forward-1-solid" /></template>
