<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qp5oynpvc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<path clip-rule="evenodd" class="qp5oynpvc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:edit-1-bold" /></template>
