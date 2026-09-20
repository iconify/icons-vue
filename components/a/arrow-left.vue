<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sbs9qlb7e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="sbs9qlb7e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mi:arrow-left" /></template>
