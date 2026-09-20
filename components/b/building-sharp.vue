<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zs9tptpik.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zs9tptpik"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:building-sharp" /></template>
