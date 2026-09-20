<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/aqwma-b7n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="aqwma-b7n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:database-remove-outline" /></template>
