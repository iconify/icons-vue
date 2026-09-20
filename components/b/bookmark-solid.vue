<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qh9zt9nng.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="qh9zt9nng"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-flex:bookmark-solid" /></template>
