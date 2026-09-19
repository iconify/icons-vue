<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b0t0adbzd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="b0t0adbzd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bxl:asana" /></template>
