<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f8be_q3jj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="f8be_q3jj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:knife-fill" /></template>
