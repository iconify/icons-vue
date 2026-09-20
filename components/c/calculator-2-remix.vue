<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c5c_lxy2s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="c5c_lxy2s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:calculator-2-remix" /></template>
