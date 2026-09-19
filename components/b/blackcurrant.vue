<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/ug29y9b4b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="ug29y9b4b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:blackcurrant" /></template>
