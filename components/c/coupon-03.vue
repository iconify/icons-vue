<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mmmkl767k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mmmkl767k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:coupon-03" /></template>
