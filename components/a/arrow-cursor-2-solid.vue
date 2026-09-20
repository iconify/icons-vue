<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ig391mlei.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="ig391mlei"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-flex:arrow-cursor-2-solid" /></template>
