<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mt-hrr_ur.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mt-hrr_ur"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-cyber:hot-beverage" /></template>
