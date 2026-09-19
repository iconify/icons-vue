<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kkiql8hbv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="kkiql8hbv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:abstract-089" /></template>
