<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o46uosa4l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="o46uosa4l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="healthicons:hospitalized-outline-24px" /></template>
