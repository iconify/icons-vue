<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o739jh8vk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<path clip-rule="evenodd" class="o739jh8vk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:filing-cabinet-bold" /></template>
