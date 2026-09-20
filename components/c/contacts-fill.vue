<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f5ym-lbnh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="f5ym-lbnh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:contacts-fill" /></template>
