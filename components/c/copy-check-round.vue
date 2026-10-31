<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mw62jpb0o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mw62jpb0o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:copy-check-round" /></template>
