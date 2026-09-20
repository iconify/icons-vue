<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/um10u-bak.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="um10u-bak"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:capitol-remix" /></template>
