<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/flcnzdvav.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="flcnzdvav"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:hearing-deaf-2-remix" /></template>
