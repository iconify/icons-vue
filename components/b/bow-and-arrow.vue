<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u_4hj9vhm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="u_4hj9vhm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji-high-contrast:bow-and-arrow" /></template>
