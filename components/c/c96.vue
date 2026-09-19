<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vxsozccmg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="vxsozccmg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:c96" /></template>
