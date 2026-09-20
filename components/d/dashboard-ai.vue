<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c_og7xf3t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="c_og7xf3t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ix:dashboard-ai" /></template>
