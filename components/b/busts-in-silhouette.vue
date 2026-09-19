<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e4oym9cew.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="e4oym9cew"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji-high-contrast:busts-in-silhouette" /></template>
