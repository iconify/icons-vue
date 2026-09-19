<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nkwvkxblq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="nkwvkxblq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:deer" /></template>
