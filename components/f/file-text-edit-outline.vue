<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cb-8vsj7h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cb-8vsj7h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:file-text-edit-outline" /></template>
