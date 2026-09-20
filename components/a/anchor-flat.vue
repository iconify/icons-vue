<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zc7uu5e1m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="zc7uu5e1m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-color:anchor-flat" /></template>
