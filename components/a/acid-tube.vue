<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/ash7njbnm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="ash7njbnm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:acid-tube" /></template>
