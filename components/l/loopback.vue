<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xrghlnb8b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xrghlnb8b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:loopback" /></template>
