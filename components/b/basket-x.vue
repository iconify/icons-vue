<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zq7mlebuk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zq7mlebuk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair-light:basket-x" /></template>
