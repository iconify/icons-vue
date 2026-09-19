<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l1-u1jbjs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="l1-u1jbjs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:lantern-flame" /></template>
