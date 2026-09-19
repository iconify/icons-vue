<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/id4wcv-7x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="id4wcv-7x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:fomorian" /></template>
