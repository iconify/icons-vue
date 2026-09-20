<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/oiz5f-b0l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="oiz5f-b0l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:calendar-2" /></template>
