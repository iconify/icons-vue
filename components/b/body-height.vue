<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/ra32g-kfq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="ra32g-kfq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:body-height" /></template>
