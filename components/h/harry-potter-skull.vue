<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jg8p__biz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="jg8p__biz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:harry-potter-skull" /></template>
