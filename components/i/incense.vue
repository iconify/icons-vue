<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/weh0b5bcz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="weh0b5bcz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:incense" /></template>
