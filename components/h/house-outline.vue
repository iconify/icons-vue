<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/iiu_lpbbz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="iiu_lpbbz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="teenyicons:house-outline" /></template>
