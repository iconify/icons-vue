<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/aof8t-bpc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="aof8t-bpc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mynaui:location-x-solid" /></template>
