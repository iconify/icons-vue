<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/t8e27lzno.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="t8e27lzno"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="quill:alarm" /></template>
