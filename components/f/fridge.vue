<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lv3bb1bsl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="lv3bb1bsl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:fridge" /></template>
