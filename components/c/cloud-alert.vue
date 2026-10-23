<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/ago928r5l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ago928r5l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vadivam:cloud-alert" /></template>
