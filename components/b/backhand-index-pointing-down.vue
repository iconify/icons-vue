<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bhnei0p-k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="bhnei0p-k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji-high-contrast:backhand-index-pointing-down" /></template>
