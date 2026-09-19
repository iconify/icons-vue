<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j350y3b4x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="j350y3b4x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:gecko" /></template>
