<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fwzbbk2dk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="fwzbbk2dk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="heroicons:cog-16-solid" /></template>
