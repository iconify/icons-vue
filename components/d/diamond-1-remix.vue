<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u9jf_1uxp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="u9jf_1uxp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-flex:diamond-1-remix" /></template>
