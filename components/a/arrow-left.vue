<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n8g-31b0v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="n8g-31b0v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="nrk:arrow-left" /></template>
