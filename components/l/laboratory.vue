<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kvn3mq7pm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kvn3mq7pm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="guidance:laboratory" /></template>
