<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hwqp_tb_b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="hwqp_tb_b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="formkit:apple" /></template>
