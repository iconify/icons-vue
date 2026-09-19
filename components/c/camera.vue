<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r6uo6chtl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":472};
const content = `<path class="r6uo6chtl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ps:camera" /></template>
