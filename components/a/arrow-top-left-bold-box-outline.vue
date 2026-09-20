<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gz4u_3b7a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gz4u_3b7a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:arrow-top-left-bold-box-outline" /></template>
