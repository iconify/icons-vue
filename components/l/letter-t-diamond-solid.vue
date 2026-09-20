<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y2smsebeb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="y2smsebeb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mynaui:letter-t-diamond-solid" /></template>
