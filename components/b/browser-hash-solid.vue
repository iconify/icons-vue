<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/coyd9vx8k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="coyd9vx8k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:browser-hash-solid" /></template>
