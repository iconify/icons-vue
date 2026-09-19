<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mzzzhdbny.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="mzzzhdbny"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="heroicons:backward-20-solid" /></template>
