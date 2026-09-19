<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lb8f1_oar.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="lb8f1_oar"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji-high-contrast:cockroach" /></template>
