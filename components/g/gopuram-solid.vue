<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lqzx1_bnr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="lqzx1_bnr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="la:gopuram-solid" /></template>
