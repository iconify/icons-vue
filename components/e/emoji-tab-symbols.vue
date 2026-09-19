<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wili7cbww.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":2048,"height":2048};
const content = `<path class="wili7cbww"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-mdl2:emoji-tab-symbols" /></template>
