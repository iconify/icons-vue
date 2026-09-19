<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p7ps3ce9b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="p7ps3ce9b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="heroicons:bars-arrow-up-16-solid" /></template>
