<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qj7n3bbpe.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<path clip-rule="evenodd" class="qj7n3bbpe"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:caret-circle-bold" /></template>
