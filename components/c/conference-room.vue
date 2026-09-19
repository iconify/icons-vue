<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yq1x5wmte.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yq1x5wmte"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="guidance:conference-room" /></template>
