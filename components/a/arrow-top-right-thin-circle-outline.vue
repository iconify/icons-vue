<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uw-a-7_ww.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="uw-a-7_ww"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:arrow-top-right-thin-circle-outline" /></template>
