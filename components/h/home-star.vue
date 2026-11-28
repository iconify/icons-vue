<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/ppj3bmbnv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ppj3bmbnv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair-light:home-star" /></template>
