<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v44wws-gq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="v44wws-gq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair-light:campfire-check" /></template>
