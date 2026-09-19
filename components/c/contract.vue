<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q1fwzm5li.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="q1fwzm5li"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:contract" /></template>
