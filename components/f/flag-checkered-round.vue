<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ia8h-s6qs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ia8h-s6qs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:flag-checkered-round" /></template>
