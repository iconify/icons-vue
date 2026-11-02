<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bm2cgccfy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bm2cgccfy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:apple-intelligence-fill" /></template>
