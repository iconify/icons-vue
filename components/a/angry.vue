<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ib5rv-b2c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ib5rv-b2c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fe:angry" /></template>
