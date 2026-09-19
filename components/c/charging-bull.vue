<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uhbj0wbch.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="uhbj0wbch"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:charging-bull" /></template>
