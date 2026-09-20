<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/oyo_hzbjm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="oyo_hzbjm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vadivam:crown" /></template>
