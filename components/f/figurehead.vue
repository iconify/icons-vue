<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/re6rncfpj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="re6rncfpj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:figurehead" /></template>
