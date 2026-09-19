<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wkuowk5pf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="wkuowk5pf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:inverted-dice-3" /></template>
