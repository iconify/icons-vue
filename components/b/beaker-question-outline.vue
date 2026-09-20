<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w7cs2_b-s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="w7cs2_b-s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:beaker-question-outline" /></template>
