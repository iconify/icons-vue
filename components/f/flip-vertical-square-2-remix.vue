<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wtpzydu5v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="wtpzydu5v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:flip-vertical-square-2-remix" /></template>
