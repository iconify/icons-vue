<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pl268cndx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="pl268cndx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:hoodie" /></template>
