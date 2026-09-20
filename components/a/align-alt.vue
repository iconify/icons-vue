<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xyqo3cbwh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xyqo3cbwh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uit:align-alt" /></template>
