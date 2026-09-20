<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lmd-mebox.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="lmd-mebox"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-flex:broken-link-1-solid" /></template>
