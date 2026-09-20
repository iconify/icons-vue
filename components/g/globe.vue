<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d407x4otp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path vector-effect="non-scaling-stroke" class="d407x4otp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="wordpress:globe" /></template>
