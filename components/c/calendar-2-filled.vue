<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/a3sc48a3v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="a3sc48a3v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:calendar-2-filled" /></template>
