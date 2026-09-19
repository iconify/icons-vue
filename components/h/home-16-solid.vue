<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fvwor_b3c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="fvwor_b3c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="heroicons:home-16-solid" /></template>
