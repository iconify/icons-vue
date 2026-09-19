<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fy5-l_xmz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fy5-l_xmz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="flowbite:icecream-alt-outline" /></template>
