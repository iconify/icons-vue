<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pqhkegbrq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":576,"height":512};
const content = `<path class="pqhkegbrq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-brands:cc-amazon-pay" /></template>
