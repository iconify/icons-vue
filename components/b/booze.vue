<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wnw_ebvht.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="wnw_ebvht"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:booze" /></template>
