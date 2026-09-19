<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/eml8ybc8c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="eml8ybc8c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:female-vampire" /></template>
