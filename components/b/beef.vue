<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/ne26k9bjf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ne26k9bjf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vadivam:beef" /></template>
