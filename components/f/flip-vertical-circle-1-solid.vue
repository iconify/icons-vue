<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/syrocm9wg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="syrocm9wg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:flip-vertical-circle-1-solid" /></template>
