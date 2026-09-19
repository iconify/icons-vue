<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/ez_yp4b6r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ez_yp4b6r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="feather:cloud-drizzle" /></template>
