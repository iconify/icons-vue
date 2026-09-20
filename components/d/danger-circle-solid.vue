<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qj6-x_bdv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qj6-x_bdv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mynaui:danger-circle-solid" /></template>
