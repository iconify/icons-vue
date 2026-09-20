<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e3l3vac6x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="e3l3vac6x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:centos-line" /></template>
