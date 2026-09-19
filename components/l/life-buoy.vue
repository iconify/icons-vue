<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gimsfve6v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="gimsfve6v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:life-buoy" /></template>
