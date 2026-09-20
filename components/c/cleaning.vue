<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tsaq0vbdd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tsaq0vbdd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:cleaning" /></template>
