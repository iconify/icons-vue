<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vqm7ajblf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="vqm7ajblf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:butterfly-flower" /></template>
