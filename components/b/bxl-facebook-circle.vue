<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vtdb6nbgf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vtdb6nbgf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bx:bxl-facebook-circle" /></template>
