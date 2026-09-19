<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n40rqhhah.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="n40rqhhah"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="heroicons-outline:bars-3-center-left" /></template>
