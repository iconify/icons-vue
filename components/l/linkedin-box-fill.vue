<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fb571flvv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fb571flvv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:linkedin-box-fill" /></template>
