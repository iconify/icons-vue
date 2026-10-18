<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dnxdv-_-v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dnxdv-_-v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vadivam:align-vertical-justify-start" /></template>
