<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/auy9bfb_f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="auy9bfb_f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:funds-box-fill" /></template>
