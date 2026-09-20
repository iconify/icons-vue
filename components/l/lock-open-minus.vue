<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uq76meb2c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="uq76meb2c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:lock-open-minus" /></template>
