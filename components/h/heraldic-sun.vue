<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wt4ee93ah.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="wt4ee93ah"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:heraldic-sun" /></template>
