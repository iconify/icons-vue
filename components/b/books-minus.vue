<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i-d5f3oms.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="i-d5f3oms"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:books-minus" /></template>
