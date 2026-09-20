<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/av-ms0saj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="av-ms0saj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vadivam:blocks" /></template>
