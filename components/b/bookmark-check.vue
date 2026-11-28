<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wku_5abjp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wku_5abjp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair-light:bookmark-check" /></template>
