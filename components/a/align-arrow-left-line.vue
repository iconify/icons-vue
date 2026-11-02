<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/thhsbm9jg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="thhsbm9jg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:align-arrow-left-line" /></template>
