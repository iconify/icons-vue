<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xf5i56b4h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="xf5i56b4h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:add-square-solid" /></template>
