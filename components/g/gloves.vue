<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rv9fke9ux.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="rv9fke9ux"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji-high-contrast:gloves" /></template>
