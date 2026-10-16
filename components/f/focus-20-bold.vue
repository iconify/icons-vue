<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/a9y9blbyi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="a9y9blbyi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:focus-20-bold" /></template>
