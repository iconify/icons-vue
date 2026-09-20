<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lfqgwlbvf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lfqgwlbvf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:luggage-cart-line" /></template>
