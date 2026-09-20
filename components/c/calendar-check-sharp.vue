<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l6gn0sbrn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="l6gn0sbrn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:calendar-check-sharp" /></template>
