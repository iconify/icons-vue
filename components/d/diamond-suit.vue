<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wp84hibku.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="wp84hibku"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji-high-contrast:diamond-suit" /></template>
