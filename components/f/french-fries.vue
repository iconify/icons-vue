<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w-0-_geiu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="w-0-_geiu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:french-fries" /></template>
