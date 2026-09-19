<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/ktpsno26x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ktpsno26x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cbi:echo-show-10" /></template>
