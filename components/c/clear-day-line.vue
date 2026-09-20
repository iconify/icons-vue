<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q9sqxibou.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="q9sqxibou"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="si:clear-day-line" /></template>
