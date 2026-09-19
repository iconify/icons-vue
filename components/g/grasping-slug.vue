<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/oya9pf1oj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="oya9pf1oj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:grasping-slug" /></template>
