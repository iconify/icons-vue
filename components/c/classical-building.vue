<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j8skr8x4h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="j8skr8x4h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:classical-building" /></template>
