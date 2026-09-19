<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h52vambzl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="h52vambzl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:kid-slide" /></template>
