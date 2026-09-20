<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/ngz-g_2fb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ngz-g_2fb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg:fanfou" /></template>
