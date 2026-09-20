<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hy16ogblb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hy16ogblb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mynaui:layout-panel-right-solid" /></template>
