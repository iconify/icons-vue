<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o5o--1q2t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="o5o--1q2t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:battery-backup" /></template>
