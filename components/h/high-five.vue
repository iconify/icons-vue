<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/ea9az7bry.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="ea9az7bry"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:high-five" /></template>
