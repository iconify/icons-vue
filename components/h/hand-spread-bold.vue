<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ikp4nxbsw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<path clip-rule="evenodd" class="ikp4nxbsw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:hand-spread-bold" /></template>
