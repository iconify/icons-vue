<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kuqwpyirs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kuqwpyirs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:calendar-x" /></template>
