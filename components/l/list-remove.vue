<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d62-adbgj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path clip-rule="evenodd" class="d62-adbgj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ix:list-remove" /></template>
