<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yian2ibvk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yian2ibvk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:futurelearn" /></template>
