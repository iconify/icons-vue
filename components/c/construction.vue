<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w5phmq9_u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":64,"height":64};
const content = `<path class="w5phmq9_u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lineicons:construction" /></template>
