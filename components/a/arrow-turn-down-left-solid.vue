<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e8ev7zbwf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="e8ev7zbwf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="heroicons:arrow-turn-down-left-solid" /></template>
