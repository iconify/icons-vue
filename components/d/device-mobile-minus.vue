<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xjd3gubjc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xjd3gubjc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:device-mobile-minus" /></template>
