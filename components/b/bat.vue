<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vukehn95i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="vukehn95i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji-high-contrast:bat" /></template>
