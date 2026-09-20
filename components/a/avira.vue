<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m7mz4q9kp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="m7mz4q9kp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="simple-icons:avira" /></template>
