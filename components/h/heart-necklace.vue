<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/ezga8i1ck.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="ezga8i1ck"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:heart-necklace" /></template>
