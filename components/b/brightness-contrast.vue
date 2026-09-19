<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fd0w13brz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="fd0w13brz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icomoon-free:brightness-contrast" /></template>
