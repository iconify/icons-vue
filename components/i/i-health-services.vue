<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vi6278x_x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":64,"height":64};
const content = `<path class="vi6278x_x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="medical-icon:i-health-services" /></template>
