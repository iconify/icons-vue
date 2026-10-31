<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/ajviypb8d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ajviypb8d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="sidekickicons:archive-box-arrow-up" /></template>
