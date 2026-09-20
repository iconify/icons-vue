<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wn6a0_m-p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wn6a0_m-p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token:forth" /></template>
