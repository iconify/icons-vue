<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/aeka40byt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="aeka40byt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-color:celsius-flat" /></template>
