<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vo5rrlbcb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vo5rrlbcb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:acer" /></template>
