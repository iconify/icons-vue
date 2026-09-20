<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fouad-q2e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fouad-q2e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:h-4" /></template>
