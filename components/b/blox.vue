<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vevmjxb3x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vevmjxb3x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token:blox" /></template>
