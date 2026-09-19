<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/km7x9fxam.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path clip-rule="evenodd" class="km7x9fxam"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="heroicons:circle-stack-20-solid" /></template>
