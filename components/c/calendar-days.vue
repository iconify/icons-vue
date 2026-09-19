<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h002_qdfn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="h002_qdfn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="heroicons-outline:calendar-days" /></template>
