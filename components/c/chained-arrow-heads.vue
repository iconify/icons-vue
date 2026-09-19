<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s6qk83b-x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="s6qk83b-x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:chained-arrow-heads" /></template>
