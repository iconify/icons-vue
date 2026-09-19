<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mwq5i-s2c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="mwq5i-s2c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji-high-contrast:exclamation-question-mark" /></template>
