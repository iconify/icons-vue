<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nfoxw2uzn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="nfoxw2uzn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:first-aid-kit" /></template>
