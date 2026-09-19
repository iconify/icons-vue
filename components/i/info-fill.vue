<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cx9_5y40s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cx9_5y40s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="eva:info-fill" /></template>
