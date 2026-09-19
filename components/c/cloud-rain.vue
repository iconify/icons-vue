<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v7hm0lwug.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="v7hm0lwug"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-solid:cloud-rain" /></template>
