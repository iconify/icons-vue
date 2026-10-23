<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pyed7fbam.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pyed7fbam"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vadivam:frame" /></template>
