<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g3rz4ufex.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="g3rz4ufex"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:bear-head" /></template>
