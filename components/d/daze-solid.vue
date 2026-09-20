<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f9a0wu13y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="f9a0wu13y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mynaui:daze-solid" /></template>
