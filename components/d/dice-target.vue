<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e_bj8hwhw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="e_bj8hwhw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:dice-target" /></template>
