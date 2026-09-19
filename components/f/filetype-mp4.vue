<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/imwdcqbzr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="imwdcqbzr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bi:filetype-mp4" /></template>
