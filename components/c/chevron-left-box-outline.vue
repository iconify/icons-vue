<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kkh4p1ded.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kkh4p1ded"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:chevron-left-box-outline" /></template>
