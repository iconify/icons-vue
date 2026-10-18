<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f-2k4oiuk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="f-2k4oiuk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vadivam:align-vertical-distribute-start" /></template>
