<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/aylyq8bhq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="aylyq8bhq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="octicon:flame-16" /></template>
