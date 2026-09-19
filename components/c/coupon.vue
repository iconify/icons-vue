<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zes3q7bnn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zes3q7bnn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bxs:coupon" /></template>
