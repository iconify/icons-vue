<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vndlk5bzx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="vndlk5bzx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bi:arrow-return-left" /></template>
