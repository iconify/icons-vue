<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z6payhbwp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="z6payhbwp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="catppuccin:ember" /></template>
