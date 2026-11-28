<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/icyuosbrk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="icyuosbrk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair-light:database-arrow-down" /></template>
