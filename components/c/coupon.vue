<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q2kgl9bwh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":8,"height":8};
const content = `<path class="q2kgl9bwh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="picon:coupon" /></template>
