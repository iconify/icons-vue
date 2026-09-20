<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/iwxu6pbnm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="iwxu6pbnm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:latitude" /></template>
