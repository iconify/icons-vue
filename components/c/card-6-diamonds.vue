<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/st6t05p-u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="st6t05p-u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:card-6-diamonds" /></template>
