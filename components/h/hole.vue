<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zbd3g8bmn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="zbd3g8bmn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:hole" /></template>
