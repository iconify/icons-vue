<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/k7d7i_big.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="k7d7i_big"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:backpack-remix" /></template>
