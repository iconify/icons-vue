<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/ju7sv0aes.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="ju7sv0aes"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-flex:iphone-remix" /></template>
