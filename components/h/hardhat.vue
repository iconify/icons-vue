<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cfrkp3b3j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="cfrkp3b3j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="catppuccin:hardhat" /></template>
