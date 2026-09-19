<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hsi4k-bcc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="hsi4k-bcc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:floor-polisher" /></template>
