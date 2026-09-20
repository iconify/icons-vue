<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o0qmd-zhd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="o0qmd-zhd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:exchange-2-line" /></template>
