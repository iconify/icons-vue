<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bk68y1fno.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="bk68y1fno"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:coal-wagon" /></template>
