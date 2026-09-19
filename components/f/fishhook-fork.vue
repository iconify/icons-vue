<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y9r3asb3k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="y9r3asb3k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:fishhook-fork" /></template>
