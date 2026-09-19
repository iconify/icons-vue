<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tav7wc75e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="tav7wc75e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:ketchup" /></template>
