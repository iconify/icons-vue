<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c4w0tp9te.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="c4w0tp9te"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bi:magnet" /></template>
