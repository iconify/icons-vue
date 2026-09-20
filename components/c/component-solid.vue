<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qd6en3etl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qd6en3etl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mynaui:component-solid" /></template>
