<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/iqvhahbwt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="iqvhahbwt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vadivam:circle-fading-plus" /></template>
