<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n5u9rbcmz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="n5u9rbcmz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:magic-palm" /></template>
