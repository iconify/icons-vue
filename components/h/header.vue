<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/t6g495_-b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":8,"height":8};
const content = `<path class="t6g495_-b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="oi:header" /></template>
