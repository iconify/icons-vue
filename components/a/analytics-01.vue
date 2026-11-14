<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y2gaezb7y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="y2gaezb7y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:analytics-01" /></template>
