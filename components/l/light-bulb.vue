<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gwmy-8bsx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="gwmy-8bsx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji-high-contrast:light-bulb" /></template>
