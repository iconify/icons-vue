<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/iboy79bkc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="iboy79bkc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:ai-chip-spark-remix" /></template>
