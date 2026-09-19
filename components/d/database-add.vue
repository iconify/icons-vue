<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ilmixgbce.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="ilmixgbce"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="dashicons:database-add" /></template>
