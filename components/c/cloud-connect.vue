<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y3uwj83vl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="y3uwj83vl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:cloud-connect" /></template>
