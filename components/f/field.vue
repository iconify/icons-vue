<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uqdqj7gbx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="uqdqj7gbx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:field" /></template>
