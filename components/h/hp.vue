<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kskmqqbfm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="kskmqqbfm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="raphael:hp" /></template>
