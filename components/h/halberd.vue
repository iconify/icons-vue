<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v8d4h96vo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="v8d4h96vo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:halberd" /></template>
