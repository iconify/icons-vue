<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l5-_om8vi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="l5-_om8vi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:arrow-left-circle-line" /></template>
