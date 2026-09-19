<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pxxyx0bqm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pxxyx0bqm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bx:bxs-cloud-download" /></template>
