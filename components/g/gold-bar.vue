<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uc1h4-8rm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="uc1h4-8rm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:gold-bar" /></template>
