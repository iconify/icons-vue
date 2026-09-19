<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lmkk5btqo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="lmkk5btqo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:avoidance" /></template>
