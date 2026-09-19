<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gsyd30fdp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="gsyd30fdp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:baton" /></template>
