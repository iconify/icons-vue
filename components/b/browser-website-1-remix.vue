<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x7s8iu7on.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="x7s8iu7on"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:browser-website-1-remix" /></template>
