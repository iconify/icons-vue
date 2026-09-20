<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h7r03-bxr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path clip-rule="evenodd" class="h7r03-bxr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="teenyicons:layers-intersect-solid" /></template>
