<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tr0t2jb7z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="tr0t2jb7z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:card-2-hearts" /></template>
