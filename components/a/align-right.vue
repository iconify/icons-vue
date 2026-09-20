<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x-x03nb1v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":8,"height":8};
const content = `<path class="x-x03nb1v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="oi:align-right" /></template>
