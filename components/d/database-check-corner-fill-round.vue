<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/joq9umt7o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="joq9umt7o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:database-check-corner-fill-round" /></template>
