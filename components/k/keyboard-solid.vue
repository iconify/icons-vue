<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ixzxp9bvq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="ixzxp9bvq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:keyboard-solid" /></template>
