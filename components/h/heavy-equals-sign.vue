<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/or7ddzi3a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="or7ddzi3a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji-high-contrast:heavy-equals-sign" /></template>
