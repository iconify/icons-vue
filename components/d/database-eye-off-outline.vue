<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rl63nfdhz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rl63nfdhz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:database-eye-off-outline" /></template>
