<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/ki8i-ccap.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":8,"height":8};
const content = `<path class="ki8i-ccap"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="picon:gamesave" /></template>
