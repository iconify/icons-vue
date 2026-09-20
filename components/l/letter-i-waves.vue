<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/k4ilc2bnr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="k4ilc2bnr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mynaui:letter-i-waves" /></template>
