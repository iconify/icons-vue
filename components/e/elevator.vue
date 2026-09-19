<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e8eyycb5t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="e8eyycb5t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:elevator" /></template>
