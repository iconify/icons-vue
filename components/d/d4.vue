<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/k9de-4b3i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="k9de-4b3i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:d4" /></template>
