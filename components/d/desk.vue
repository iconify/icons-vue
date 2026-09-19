<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gg1bb7shi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="gg1bb7shi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:desk" /></template>
