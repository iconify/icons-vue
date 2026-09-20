<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i1i8s8bks.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="i1i8s8bks"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:keyboard-box-fill" /></template>
