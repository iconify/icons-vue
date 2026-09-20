<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cvrgf19zw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cvrgf19zw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:lan-check" /></template>
