<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tb3qe19hc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="tb3qe19hc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:eruption" /></template>
