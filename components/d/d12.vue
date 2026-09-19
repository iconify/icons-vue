<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lh52kebye.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="lh52kebye"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:d12" /></template>
