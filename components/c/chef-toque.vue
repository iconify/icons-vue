<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vug7zdb2j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="vug7zdb2j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:chef-toque" /></template>
