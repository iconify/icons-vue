<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/ewplzhb4s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="ewplzhb4s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:bus" /></template>
