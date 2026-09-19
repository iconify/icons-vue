<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/ckwx5iwly.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="ckwx5iwly"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:fire-gem" /></template>
