<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fxk9dhkgu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fxk9dhkgu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:download-cloud-fill" /></template>
