<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cto-b0f_o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cto-b0f_o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:funds-fill" /></template>
