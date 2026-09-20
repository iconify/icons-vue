<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n4u5icbnv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="n4u5icbnv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mynaui:bookmark-minus-solid" /></template>
