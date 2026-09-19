<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r3djdxbeb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="r3djdxbeb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:card-9-hearts" /></template>
