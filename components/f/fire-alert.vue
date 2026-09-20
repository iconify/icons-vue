<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d8-_su0fv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="d8-_su0fv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:fire-alert" /></template>
