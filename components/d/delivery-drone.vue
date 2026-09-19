<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/ro3btb_ny.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="ro3btb_ny"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:delivery-drone" /></template>
