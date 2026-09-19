<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pve4lhbsq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="pve4lhbsq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji-high-contrast:check-box-with-check" /></template>
