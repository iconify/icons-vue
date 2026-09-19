<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uh_kfwb3g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="uh_kfwb3g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:ak47u" /></template>
