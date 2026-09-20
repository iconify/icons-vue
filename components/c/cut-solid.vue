<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zs413g27j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="zs413g27j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:cut-solid" /></template>
