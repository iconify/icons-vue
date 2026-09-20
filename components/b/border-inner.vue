<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hos4_h6il.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hos4_h6il"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uil:border-inner" /></template>
