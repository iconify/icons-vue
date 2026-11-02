<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f_zw-6bfz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="f_zw-6bfz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:disabled-2-fill" /></template>
