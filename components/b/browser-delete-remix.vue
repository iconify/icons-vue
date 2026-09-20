<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/ei_60e-bn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="ei_60e-bn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:browser-delete-remix" /></template>
