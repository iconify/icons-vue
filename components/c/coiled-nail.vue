<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v88u9dbqr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="v88u9dbqr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:coiled-nail" /></template>
