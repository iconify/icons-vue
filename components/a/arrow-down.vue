<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/ux6_y-bdg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ux6_y-bdg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="heroicons:arrow-down" /></template>
