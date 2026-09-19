<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xzvqo1krd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<path clip-rule="evenodd" class="xzvqo1krd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:battery-outline" /></template>
