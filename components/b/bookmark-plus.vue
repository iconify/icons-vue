<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fbrtfx9pu.css';
import '../../css/s/s9jq5ybcb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fbrtfx9pu"/><path class="s9jq5ybcb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:bookmark-plus" /></template>
