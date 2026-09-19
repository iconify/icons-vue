<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hp4izd5vt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="hp4izd5vt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="catppuccin:folder-open" /></template>
