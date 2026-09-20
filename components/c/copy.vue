<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yv1-oda_u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yv1-oda_u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vadivam:copy" /></template>
