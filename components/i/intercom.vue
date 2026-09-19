<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vetpb2ele.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vetpb2ele"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bxl:intercom" /></template>
