<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c9j188ytp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="c9j188ytp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair:bank-lock" /></template>
