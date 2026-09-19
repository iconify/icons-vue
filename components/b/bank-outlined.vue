<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hpspd0b0x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":1024};
const content = `<path class="hpspd0b0x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ant-design:bank-outlined" /></template>
