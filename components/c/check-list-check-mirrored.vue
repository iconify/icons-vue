<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i6ncrbthp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":2048,"height":2048};
const content = `<path class="i6ncrbthp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-mdl2:check-list-check-mirrored" /></template>
