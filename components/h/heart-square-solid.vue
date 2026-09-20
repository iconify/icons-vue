<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wz3pgizbp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wz3pgizbp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mynaui:heart-square-solid" /></template>
