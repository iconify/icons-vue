<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h-pn7fboi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="h-pn7fboi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:arrow-expand-diagonal-02" /></template>
