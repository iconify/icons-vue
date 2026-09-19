<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o96j-bnpx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="o96j-bnpx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:balcony" /></template>
