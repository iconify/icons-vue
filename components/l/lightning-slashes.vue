<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c9z6qm4bq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="c9z6qm4bq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:lightning-slashes" /></template>
