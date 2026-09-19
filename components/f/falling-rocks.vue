<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dp9goebau.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dp9goebau"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="guidance:falling-rocks" /></template>
