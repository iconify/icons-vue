<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/un82zp0vv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="un82zp0vv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:i-brick" /></template>
