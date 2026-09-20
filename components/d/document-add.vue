<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mpd7mvmhe.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="mpd7mvmhe"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="zondicons:document-add" /></template>
