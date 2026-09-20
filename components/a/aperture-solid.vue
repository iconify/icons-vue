<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qimiy-xzm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qimiy-xzm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mynaui:aperture-solid" /></template>
