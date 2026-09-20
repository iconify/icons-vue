<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nig-dl-ab.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nig-dl-ab"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:bus-line" /></template>
