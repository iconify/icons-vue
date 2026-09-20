<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c3ji-cbnb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="c3ji-cbnb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:ai-science-spark-remix" /></template>
