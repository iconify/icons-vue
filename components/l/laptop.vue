<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p-vgquoff.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1920,"height":1280};
const content = `<path class="p-vgquoff"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa:laptop" /></template>
