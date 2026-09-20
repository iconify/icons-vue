<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pfqmicchz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pfqmicchz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mynaui:cart-plus" /></template>
