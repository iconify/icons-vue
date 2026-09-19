<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xz6id2bed.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="xz6id2bed"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icomoon-free:equalizer" /></template>
