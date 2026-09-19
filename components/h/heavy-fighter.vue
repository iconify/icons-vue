<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kwvkgnb5j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="kwvkgnb5j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:heavy-fighter" /></template>
