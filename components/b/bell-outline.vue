<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xto9lgpmg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xto9lgpmg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="eva:bell-outline" /></template>
