<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c_b_chb7e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="c_b_chb7e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:diamond-square-fill" /></template>
