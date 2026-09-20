<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xym3lyf4i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xym3lyf4i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mynaui:ban-solid" /></template>
