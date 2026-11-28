<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wo-bkgbdf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wo-bkgbdf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair-light:cloud-sun" /></template>
