<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dd_4b-b2g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="dd_4b-b2g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:bestial-fangs" /></template>
