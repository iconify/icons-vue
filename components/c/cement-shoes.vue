<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l86ufdcfq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="l86ufdcfq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:cement-shoes" /></template>
