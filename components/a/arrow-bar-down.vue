<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vo449e5to.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="vo449e5to"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bi:arrow-bar-down" /></template>
