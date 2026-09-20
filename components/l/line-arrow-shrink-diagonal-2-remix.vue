<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/ytpw9bbls.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="ytpw9bbls"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:line-arrow-shrink-diagonal-2-remix" /></template>
