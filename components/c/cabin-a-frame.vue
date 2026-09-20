<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mfvfk1bqy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mfvfk1bqy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:cabin-a-frame" /></template>
