<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pfe3tgbcc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="pfe3tgbcc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji-high-contrast:black-cat" /></template>
