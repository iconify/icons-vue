<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j9-41acwm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="j9-41acwm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:cruiser" /></template>
