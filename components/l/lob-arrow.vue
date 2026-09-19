<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wtjx-7-rw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="wtjx-7-rw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:lob-arrow" /></template>
