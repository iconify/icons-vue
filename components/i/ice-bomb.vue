<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bwt9oobxw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="bwt9oobxw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:ice-bomb" /></template>
