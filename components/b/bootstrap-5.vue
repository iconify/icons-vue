<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hn6178bcr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="hn6178bcr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lineicons:bootstrap-5" /></template>
