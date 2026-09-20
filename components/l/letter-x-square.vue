<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zm74ufbis.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zm74ufbis"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mynaui:letter-x-square" /></template>
