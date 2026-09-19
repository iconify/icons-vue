<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y4yqpq1og.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="y4yqpq1og"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="file-icons:assembly-avr" /></template>
