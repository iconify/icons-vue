<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nb_zv80mu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="nb_zv80mu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji-high-contrast:construction" /></template>
