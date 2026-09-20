<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tcc-r0bkj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tcc-r0bkj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:books-variant" /></template>
