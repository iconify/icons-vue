<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hnh3-2b2a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hnh3-2b2a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:arrow-left-long-fill" /></template>
