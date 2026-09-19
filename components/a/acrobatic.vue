<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zo_-f-osg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="zo_-f-osg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:acrobatic" /></template>
