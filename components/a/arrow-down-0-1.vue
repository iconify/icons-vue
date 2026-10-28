<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gy5gpbcfp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gy5gpbcfp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vadivam:arrow-down-0-1" /></template>
