<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z9_cz0n8z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="z9_cz0n8z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-flex:copy-2-remix" /></template>
