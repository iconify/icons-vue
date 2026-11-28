<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mos_254bb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mos_254bb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:book-plus-solid" /></template>
