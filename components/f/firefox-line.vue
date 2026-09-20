<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bwxyczbiu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bwxyczbiu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:firefox-line" /></template>
