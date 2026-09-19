<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/izx-16bdk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="izx-16bdk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="griddy-icons:loyalty-card-alt-filled" /></template>
