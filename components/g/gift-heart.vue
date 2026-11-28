<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/ayoli9bxt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ayoli9bxt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair:gift-heart" /></template>
