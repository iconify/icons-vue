<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/itdsf40ga.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path clip-rule="evenodd" class="itdsf40ga"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="heroicons:arrow-turn-right-up-20-solid" /></template>
