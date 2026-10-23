<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/di3bevppd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="di3bevppd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vadivam:flask-conical" /></template>
