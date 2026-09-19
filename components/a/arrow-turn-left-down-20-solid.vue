<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/k7x7srsks.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path clip-rule="evenodd" class="k7x7srsks"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="heroicons:arrow-turn-left-down-20-solid" /></template>
