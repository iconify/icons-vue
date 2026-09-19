<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/we22wodmu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="we22wodmu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="catppuccin:android" /></template>
