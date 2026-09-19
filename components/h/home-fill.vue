<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i2wti8bik.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="i2wti8bik"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ci:home-fill" /></template>
