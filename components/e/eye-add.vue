<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r5lb52u8d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="r5lb52u8d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:eye-add" /></template>
