<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/ljh_osb8l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ljh_osb8l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide:grid-2x2-check" /></template>
