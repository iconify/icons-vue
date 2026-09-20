<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vmc-tbbfp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vmc-tbbfp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:battery-plus" /></template>
