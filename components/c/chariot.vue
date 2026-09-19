<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zwchpxb5r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="zwchpxb5r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:chariot" /></template>
