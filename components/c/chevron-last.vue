<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cwv11hbwy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cwv11hbwy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide:chevron-last" /></template>
