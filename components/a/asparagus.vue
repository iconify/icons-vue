<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/atsojk9me.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="atsojk9me"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:asparagus" /></template>
