<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s9jh4ctai.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="s9jh4ctai"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:layout-8-fill" /></template>
