<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u25sb9b5k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1200,"height":1200};
const content = `<path class="u25sb9b5k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="el:lastfm" /></template>
