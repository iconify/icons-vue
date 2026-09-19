<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m1f07vhbt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="m1f07vhbt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:juggling-clubs" /></template>
