<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gy9p3gbal.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gy9p3gbal"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:butterfly" /></template>
