<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/en4s_dyhr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="en4s_dyhr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mynaui:heart-broken-solid" /></template>
