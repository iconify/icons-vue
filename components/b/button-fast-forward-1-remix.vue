<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/izb-tjjqc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="izb-tjjqc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:button-fast-forward-1-remix" /></template>
