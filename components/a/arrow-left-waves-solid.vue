<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f8eu9ebpy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="f8eu9ebpy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mynaui:arrow-left-waves-solid" /></template>
