<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w7wgwdbqd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="w7wgwdbqd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="heroicons:h1-16-solid" /></template>
