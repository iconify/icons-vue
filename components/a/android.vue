<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nh4pq_8fd.css';
import '../../css/e/ebhrip5sz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="duoicon-primary-layer nh4pq_8fd"/><path class="duoicon-secondary-layer ebhrip5sz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="duo-icons:android" /></template>
