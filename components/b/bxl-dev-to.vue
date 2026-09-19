<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/t03cpykmm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="t03cpykmm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bx:bxl-dev-to" /></template>
