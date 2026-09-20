<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n7ql-2g6j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="n7ql-2g6j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:brightness-2-remix" /></template>
