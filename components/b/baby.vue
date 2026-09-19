<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p_no2n83c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":640};
const content = `<path class="p_no2n83c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa7-solid:baby" /></template>
