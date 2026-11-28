<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rtrcekbln.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rtrcekbln"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:circle-number-2-solid" /></template>
