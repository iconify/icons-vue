<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/k12xm9bhl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="k12xm9bhl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:credit-card-scan" /></template>
