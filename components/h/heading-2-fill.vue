<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bupor9x0f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bupor9x0f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:heading-2-fill" /></template>
