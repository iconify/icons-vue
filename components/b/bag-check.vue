<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c-oygbbiy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="c-oygbbiy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair-light:bag-check" /></template>
