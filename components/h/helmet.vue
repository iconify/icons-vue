<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tgzalccnk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="tgzalccnk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:helmet" /></template>
