<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wtfey4brq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="wtfey4brq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:gloves" /></template>
