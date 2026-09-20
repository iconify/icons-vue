<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yc_3mkezm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yc_3mkezm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:cordova" /></template>
