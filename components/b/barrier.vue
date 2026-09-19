<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hbr5iv52a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="hbr5iv52a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:barrier" /></template>
