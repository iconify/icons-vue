<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tq-uyeb3b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tq-uyeb3b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconamoon:location-light" /></template>
