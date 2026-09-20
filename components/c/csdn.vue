<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wq71p08_x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wq71p08_x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:csdn" /></template>
