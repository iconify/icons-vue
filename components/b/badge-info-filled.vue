<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sy0s7rb0s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="sy0s7rb0s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:badge-info-filled" /></template>
