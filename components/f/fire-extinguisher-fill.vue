<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/ku7oxq-5t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ku7oxq-5t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:fire-extinguisher-fill" /></template>
