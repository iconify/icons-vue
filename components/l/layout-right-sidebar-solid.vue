<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vuv7_qo5p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="vuv7_qo5p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-flex:layout-right-sidebar-solid" /></template>
