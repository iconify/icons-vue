<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f9dvr0bhq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="f9dvr0bhq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:forest-camp" /></template>
