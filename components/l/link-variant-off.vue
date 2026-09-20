<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o32rc1bqm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="o32rc1bqm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:link-variant-off" /></template>
