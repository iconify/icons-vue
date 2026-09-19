<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/ykmdt0bsi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":17,"height":16};
const content = `<path class="ykmdt0bsi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="si-glyph:like-unlike" /></template>
