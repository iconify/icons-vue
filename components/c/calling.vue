<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/oh38vkbhw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="oh38vkbhw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:calling" /></template>
