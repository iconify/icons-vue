<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/csit38b6l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="csit38b6l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:light-thorny-triskelion" /></template>
