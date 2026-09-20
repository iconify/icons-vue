<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fio3r8-yl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fio3r8-yl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:actual-budget" /></template>
