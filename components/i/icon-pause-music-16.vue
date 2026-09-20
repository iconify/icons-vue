<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sjowf5brh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="sjowf5brh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="qlementine-icons:icon-pause-music-16" /></template>
