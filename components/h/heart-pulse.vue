<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sz8tqk1vi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="sz8tqk1vi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vadivam:heart-pulse" /></template>
