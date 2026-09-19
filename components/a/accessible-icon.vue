<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/ppl-i9bjl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":640};
const content = `<path class="ppl-i9bjl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa7-brands:accessible-icon" /></template>
