<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z0jo-47we.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="z0jo-47we"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:calendar-pause" /></template>
