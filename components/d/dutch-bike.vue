<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u8ioll_bk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="u8ioll_bk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:dutch-bike" /></template>
