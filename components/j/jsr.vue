<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fb-q3w5sr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="fb-q3w5sr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-icon-theme:jsr" /></template>
