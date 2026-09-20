<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hizanpbtx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hizanpbtx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:circle-percentage-filled" /></template>
