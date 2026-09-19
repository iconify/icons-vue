<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rpx6p7ooe.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":17,"height":16};
const content = `<path class="rpx6p7ooe"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="si-glyph:deny" /></template>
