<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qx74kcluf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qx74kcluf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="eva:briefcase-outline" /></template>
