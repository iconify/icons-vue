<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z3nac0baa.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="z3nac0baa"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="teenyicons:bag-solid" /></template>
