<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tp71m8bfx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tp71m8bfx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi-light:ereader" /></template>
