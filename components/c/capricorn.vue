<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cevh89b7w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="cevh89b7w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji-high-contrast:capricorn" /></template>
