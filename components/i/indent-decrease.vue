<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zg0_1ub4c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zg0_1ub4c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:indent-decrease" /></template>
