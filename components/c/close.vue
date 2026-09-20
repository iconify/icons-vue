<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bhqhz4brg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bhqhz4brg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tdesign:close" /></template>
