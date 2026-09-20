<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/ym_0hibad.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ym_0hibad"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:book-shelf-fill" /></template>
