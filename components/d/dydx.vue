<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vfl__x7jo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vfl__x7jo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token:dydx" /></template>
