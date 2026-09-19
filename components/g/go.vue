<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wydr1jbrf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="wydr1jbrf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="catppuccin:go" /></template>
