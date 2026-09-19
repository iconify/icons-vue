<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mr-lwlbzj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="mr-lwlbzj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:boomerang-cross" /></template>
