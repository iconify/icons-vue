<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/a_3imtbwy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="a_3imtbwy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:fan-minus" /></template>
