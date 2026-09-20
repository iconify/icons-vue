<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nypu68bru.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nypu68bru"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:cloud-connection" /></template>
