<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l82b-3bxw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="l82b-3bxw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:fall-down" /></template>
