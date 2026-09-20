<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y5vcvsr_c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="y5vcvsr_c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:collapse-diagonal-2-line" /></template>
