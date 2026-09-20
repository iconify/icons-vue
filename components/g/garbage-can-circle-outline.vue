<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x-69nqguz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="x-69nqguz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:garbage-can-circle-outline" /></template>
