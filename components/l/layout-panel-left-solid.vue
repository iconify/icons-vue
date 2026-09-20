<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/ws4ta_bbw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ws4ta_bbw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mynaui:layout-panel-left-solid" /></template>
