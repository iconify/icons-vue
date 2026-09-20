<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/eyjewsblq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="eyjewsblq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:briefcase-download-outline" /></template>
