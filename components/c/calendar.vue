<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yiwlzdz7u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yiwlzdz7u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fe:calendar" /></template>
