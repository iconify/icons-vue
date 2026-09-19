<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lsojb92fe.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="lsojb92fe"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:dove" /></template>
