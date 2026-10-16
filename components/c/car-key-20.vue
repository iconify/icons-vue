<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lyz2lacbc.css';
import '../../css/g/g51el4b_s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="lyz2lacbc"/><path class="g51el4b_s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:car-key-20" /></template>
