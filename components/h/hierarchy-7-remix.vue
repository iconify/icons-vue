<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f7z7gccfy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="f7z7gccfy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:hierarchy-7-remix" /></template>
