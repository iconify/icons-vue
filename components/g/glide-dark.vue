<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y5sfl_b0u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":100,"height":100};
const content = `<path class="y5sfl_b0u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:glide-dark" /></template>
