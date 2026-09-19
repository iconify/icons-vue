<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/a5w9ww-gj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="a5w9ww-gj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:jupiter" /></template>
