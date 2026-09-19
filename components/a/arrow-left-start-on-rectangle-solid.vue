<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/t3jl3kb1y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="t3jl3kb1y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="heroicons:arrow-left-start-on-rectangle-solid" /></template>
