<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/anq_8t-3h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="anq_8t-3h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="qlementine-icons:icon-start-music-16" /></template>
