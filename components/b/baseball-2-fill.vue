<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o8j6vh2mv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="o8j6vh2mv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:baseball-2-fill" /></template>
