<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rhh9iqynz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rhh9iqynz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mynaui:letter-j-solid" /></template>
