<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gy08xob7x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gy08xob7x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:blaze-fill" /></template>
