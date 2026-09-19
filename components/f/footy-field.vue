<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rlg952n0i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="rlg952n0i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:footy-field" /></template>
