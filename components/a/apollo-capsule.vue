<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tj3psbbfy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="tj3psbbfy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:apollo-capsule" /></template>
