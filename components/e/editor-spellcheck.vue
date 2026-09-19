<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xz7yt3bvs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="xz7yt3bvs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="dashicons:editor-spellcheck" /></template>
