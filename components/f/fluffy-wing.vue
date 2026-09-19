<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u56k5mb2g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="u56k5mb2g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:fluffy-wing" /></template>
