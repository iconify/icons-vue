<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sa5vtea9e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="sa5vtea9e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:grid-2x2-check-filled" /></template>
