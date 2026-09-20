<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hk0-0lbcm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hk0-0lbcm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uil:forwaded-call" /></template>
