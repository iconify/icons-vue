<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e3bzb4bff.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="e3bzb4bff"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:code-less-than-or-equal" /></template>
