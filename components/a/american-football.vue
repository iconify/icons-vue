<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o180gvvzm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="o180gvvzm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji-high-contrast:american-football" /></template>
