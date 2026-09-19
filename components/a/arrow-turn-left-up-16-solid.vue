<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/ub05ksbjs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="ub05ksbjs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="heroicons:arrow-turn-left-up-16-solid" /></template>
