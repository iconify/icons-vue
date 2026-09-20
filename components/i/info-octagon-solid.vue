<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lmwuo7c7q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lmwuo7c7q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mynaui:info-octagon-solid" /></template>
