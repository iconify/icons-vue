<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dmz_4mbgd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="dmz_4mbgd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:face-dizzy-filled" /></template>
