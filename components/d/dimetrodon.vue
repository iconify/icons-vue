<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/ni2wf1t7r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="ni2wf1t7r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:dimetrodon" /></template>
