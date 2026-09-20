<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nho-2e7vi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nho-2e7vi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pixel:flag-checkered" /></template>
