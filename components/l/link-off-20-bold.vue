<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gn_u8juie.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="gn_u8juie"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:link-off-20-bold" /></template>
