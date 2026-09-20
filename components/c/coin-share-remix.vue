<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x0pblu2cu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="x0pblu2cu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-flex:coin-share-remix" /></template>
