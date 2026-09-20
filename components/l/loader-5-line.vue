<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sl8-tc6le.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="sl8-tc6le"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:loader-5-line" /></template>
