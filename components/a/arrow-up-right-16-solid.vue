<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/t9wgamtdz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="t9wgamtdz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="heroicons:arrow-up-right-16-solid" /></template>
