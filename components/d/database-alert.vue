<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xoydhk-ol.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xoydhk-ol"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair-light:database-alert" /></template>
