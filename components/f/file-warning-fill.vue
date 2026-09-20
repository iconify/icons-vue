<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/al9_oyb8d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="al9_oyb8d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:file-warning-fill" /></template>
