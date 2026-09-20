<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/riu_o1bcx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":8,"height":8};
const content = `<path class="riu_o1bcx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="oi:credit-card" /></template>
