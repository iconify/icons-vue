<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wimvd-lkf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wimvd-lkf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair-light:bone-alert" /></template>
