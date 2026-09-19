<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fr8bhqlfy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="fr8bhqlfy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:lightning-shout" /></template>
