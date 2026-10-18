<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/eqidrqohi.css';
import '../../css/m/mq0070biz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="eqidrqohi"/><path class="mq0070biz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:green-jobs-48-bold" /></template>
