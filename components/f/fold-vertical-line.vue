<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fku2rgopk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fku2rgopk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:fold-vertical-line" /></template>
