<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p7s00cewr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="p7s00cewr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:desk" /></template>
