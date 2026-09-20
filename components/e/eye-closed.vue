<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z2uszoujg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":14};
const content = `<path class="z2uszoujg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="octicon:eye-closed" /></template>
