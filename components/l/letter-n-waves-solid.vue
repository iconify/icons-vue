<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yj95-8veb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yj95-8veb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mynaui:letter-n-waves-solid" /></template>
