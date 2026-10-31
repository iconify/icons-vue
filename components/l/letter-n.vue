<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/iyfm_1-bm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="iyfm_1-bm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vadivam:letter-n" /></template>
