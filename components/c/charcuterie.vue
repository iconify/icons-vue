<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qra3ppi9u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="qra3ppi9u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:charcuterie" /></template>
