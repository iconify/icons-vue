<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e3az1bq5g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="e3az1bq5g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:bomber" /></template>
