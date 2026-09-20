<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zm0pnqbcz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="zm0pnqbcz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:hand-stars-outline" /></template>
