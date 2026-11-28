<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/isj2kzbat.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="isj2kzbat"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair-light:basket-heart" /></template>
