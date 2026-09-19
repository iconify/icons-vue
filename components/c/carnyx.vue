<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pba9wvbwd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="pba9wvbwd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:carnyx" /></template>
