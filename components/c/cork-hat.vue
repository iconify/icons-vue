<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tz2_bykhj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="tz2_bykhj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:cork-hat" /></template>
