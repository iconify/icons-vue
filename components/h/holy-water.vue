<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uh5t2xsar.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="uh5t2xsar"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:holy-water" /></template>
