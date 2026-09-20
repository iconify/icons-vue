<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/ywfef-bqc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ywfef-bqc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:file-word-2-fill" /></template>
