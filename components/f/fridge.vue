<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/aiep-3mai.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="aiep-3mai"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:fridge" /></template>
