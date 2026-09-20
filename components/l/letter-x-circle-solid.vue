<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wuggqv5-p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wuggqv5-p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mynaui:letter-x-circle-solid" /></template>
