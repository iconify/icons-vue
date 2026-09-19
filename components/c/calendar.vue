<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zvh67cbpf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zvh67cbpf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="guidance:calendar" /></template>
