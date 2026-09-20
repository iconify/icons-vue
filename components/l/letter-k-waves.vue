<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o9dq5q5ke.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="o9dq5q5ke"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mynaui:letter-k-waves" /></template>
