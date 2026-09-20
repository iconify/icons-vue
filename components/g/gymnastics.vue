<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f3uh0acvd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="f3uh0acvd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:gymnastics" /></template>
