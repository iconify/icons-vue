<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e48hl62yw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="e48hl62yw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:fingerprint-2-line" /></template>
