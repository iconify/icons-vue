<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bbiw6mb8g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="bbiw6mb8g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji-high-contrast:bell-pepper" /></template>
