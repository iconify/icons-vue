<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/ji3u0zbnc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="ji3u0zbnc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icomoon-free:lastfm" /></template>
