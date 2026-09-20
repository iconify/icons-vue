<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/oauynmb4i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="oauynmb4i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mynaui:cookie-solid" /></template>
