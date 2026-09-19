<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xacu0mbvv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="xacu0mbvv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:fire-breath" /></template>
