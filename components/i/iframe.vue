<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qv_hzn8gl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qv_hzn8gl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:iframe" /></template>
