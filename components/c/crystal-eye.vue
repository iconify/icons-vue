<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sm1u20b0c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="sm1u20b0c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:crystal-eye" /></template>
