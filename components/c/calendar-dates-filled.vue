<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q5fqdlybr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="q5fqdlybr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="griddy-icons:calendar-dates-filled" /></template>
