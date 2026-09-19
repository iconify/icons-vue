<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r64x3ubrb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<rect class="r64x3ubrb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="gg:loadbar" /></template>
