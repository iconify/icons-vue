<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m8lp-bu2q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="m8lp-bu2q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:brandy-bottle" /></template>
