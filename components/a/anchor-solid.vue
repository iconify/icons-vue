<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zxsbno4fy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="zxsbno4fy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:anchor-solid" /></template>
