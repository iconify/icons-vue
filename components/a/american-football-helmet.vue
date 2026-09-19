<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/t74_h4bla.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="t74_h4bla"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:american-football-helmet" /></template>
