<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gszfr8bjl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gszfr8bjl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:chevron-last-solid" /></template>
