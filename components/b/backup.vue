<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y8a3nqbin.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="y8a3nqbin"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:backup" /></template>
