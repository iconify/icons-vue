<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/doceul2pl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="doceul2pl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="weui:home-outlined" /></template>
