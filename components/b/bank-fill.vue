<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sbyr_s4ar.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":1024};
const content = `<path class="sbyr_s4ar"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ant-design:bank-fill" /></template>
