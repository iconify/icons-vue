<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c8n9ys8jf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":896,"height":1024};
const content = `<path class="c8n9ys8jf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="whh:doubletap" /></template>
