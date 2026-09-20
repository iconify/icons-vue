<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r18p76buy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="r18p76buy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:color-tuning-filled" /></template>
