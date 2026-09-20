<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/ah4pulxlj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="ah4pulxlj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:like-1-remix" /></template>
