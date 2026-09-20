<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/au420xd-e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="au420xd-e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:align-vertical-centre" /></template>
