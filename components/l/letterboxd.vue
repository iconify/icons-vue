<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/eysv7-b1j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="b eysv7-b1j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bxl:letterboxd" /></template>
