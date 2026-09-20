<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zl68r0buz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="zl68r0buz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-plump-color:cog-flat" /></template>
