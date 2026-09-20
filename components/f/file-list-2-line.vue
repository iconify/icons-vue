<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cr3ricc3s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cr3ricc3s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:file-list-2-line" /></template>
