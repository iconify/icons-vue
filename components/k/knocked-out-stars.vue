<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z86n8gb9j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="z86n8gb9j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:knocked-out-stars" /></template>
