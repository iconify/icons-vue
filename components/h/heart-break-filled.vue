<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/ack44lzzv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ack44lzzv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:heart-break-filled" /></template>
