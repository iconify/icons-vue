<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e72c6_bdb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="e72c6_bdb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:figma-solid" /></template>
