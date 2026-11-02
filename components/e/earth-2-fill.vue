<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/heco3vfik.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="heco3vfik"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:earth-2-fill" /></template>
