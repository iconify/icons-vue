<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/t7w0psy3j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="t7w0psy3j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:direction-signs" /></template>
