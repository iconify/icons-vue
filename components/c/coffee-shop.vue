<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wndjwo3_c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wndjwo3_c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="guidance:coffee-shop" /></template>
