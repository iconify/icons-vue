<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cf60v8bar.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cf60v8bar"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:calendar-text-round" /></template>
