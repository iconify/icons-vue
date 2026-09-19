<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j3h-9fb2n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="j3h-9fb2n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji-high-contrast:bell" /></template>
