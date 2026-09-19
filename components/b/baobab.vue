<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tgmz_5ssx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="tgmz_5ssx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:baobab" /></template>
