<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/ai-hwv_fk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="ai-hwv_fk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:exclamation-point-beside-exclamation-point" /></template>
