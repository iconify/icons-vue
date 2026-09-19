<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vjbr___sf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="vjbr___sf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="heroicons:hand-raised-16-solid" /></template>
