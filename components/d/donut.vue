<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v3po1xfsj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="v3po1xfsj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fe:donut" /></template>
