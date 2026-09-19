<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/enr6_dbmo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="enr6_dbmo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoir:bubble-upload" /></template>
