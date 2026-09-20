<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r-yn6nltx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="r-yn6nltx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:cart-shop-filled" /></template>
