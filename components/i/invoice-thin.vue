<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zkcaf3e7x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zkcaf3e7x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconamoon:invoice-thin" /></template>
