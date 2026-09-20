<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jhflnybkg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jhflnybkg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:hours-24" /></template>
