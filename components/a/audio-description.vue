<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kvk_-kegd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":640};
const content = `<path class="kvk_-kegd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa7-solid:audio-description" /></template>
