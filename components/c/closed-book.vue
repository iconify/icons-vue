<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/a4atj1bsn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="a4atj1bsn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji-high-contrast:closed-book" /></template>
