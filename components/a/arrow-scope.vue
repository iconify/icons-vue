<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/ezqx5ys9z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="ezqx5ys9z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:arrow-scope" /></template>
