<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/ucz9flbsv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="ucz9flbsv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:bottled-bolt" /></template>
