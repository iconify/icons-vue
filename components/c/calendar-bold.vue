<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p8ul7ibqd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<path clip-rule="evenodd" class="p8ul7ibqd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:calendar-bold" /></template>
