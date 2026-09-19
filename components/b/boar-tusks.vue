<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sx7h1gakz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="sx7h1gakz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:boar-tusks" /></template>
