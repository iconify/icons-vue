<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vir9iiboj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vir9iiboj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:asus" /></template>
