<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wrr2tobrp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wrr2tobrp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:forward-30-line" /></template>
