<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zwzkrzn5e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="zwzkrzn5e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="catppuccin:dhall" /></template>
