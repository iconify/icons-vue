<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bd66ni5am.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="bd66ni5am"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji-high-contrast:anger-symbol" /></template>
