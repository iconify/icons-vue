<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hz3cmqw6d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hz3cmqw6d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bx:bx-chevron-down" /></template>
