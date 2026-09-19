<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uc-ogab1s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="uc-ogab1s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:ladder" /></template>
