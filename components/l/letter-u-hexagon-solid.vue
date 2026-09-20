<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x14s3jbek.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="x14s3jbek"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mynaui:letter-u-hexagon-solid" /></template>
