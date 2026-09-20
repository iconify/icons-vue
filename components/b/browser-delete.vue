<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/efeitt0fa.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path class="efeitt0fa"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:browser-delete" /></template>
