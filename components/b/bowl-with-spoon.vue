<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sxz7cltnn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="sxz7cltnn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji-high-contrast:bowl-with-spoon" /></template>
