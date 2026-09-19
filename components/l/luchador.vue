<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vyc6-gqkv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="vyc6-gqkv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:luchador" /></template>
