<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/scf128k4e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="scf128k4e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:dress-01" /></template>
