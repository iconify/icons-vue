<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/viimxnb_o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":448,"height":512};
const content = `<path class="viimxnb_o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa-solid:border-style" /></template>
