<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zh210v_jq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<path clip-rule="evenodd" class="zh210v_jq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:grin-beam-bold" /></template>
