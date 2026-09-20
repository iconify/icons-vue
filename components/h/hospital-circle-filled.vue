<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sqi5v1bhf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="sqi5v1bhf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:hospital-circle-filled" /></template>
